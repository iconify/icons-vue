<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6-vpyb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6-vpyb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:gift-box-outline" /></template>
