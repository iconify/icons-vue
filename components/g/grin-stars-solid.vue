<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrhp4jdbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wrhp4jdbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grin-stars-solid" /></template>
