<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmq22nb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmq22nb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:horizontal-switch-light" /></template>
