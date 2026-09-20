<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7wecmdvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7wecmdvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-up-box-line" /></template>
