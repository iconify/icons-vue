<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp-qfljmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp-qfljmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ad-solid" /></template>
