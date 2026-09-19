<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skta_czup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skta_czup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chevron-left-solid" /></template>
