<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyuucdcbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyuucdcbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:label-solid" /></template>
