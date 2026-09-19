<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q35elrbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q35elrbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bed-solid" /></template>
