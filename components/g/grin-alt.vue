<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxaimzbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pxaimzbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grin-alt" /></template>
