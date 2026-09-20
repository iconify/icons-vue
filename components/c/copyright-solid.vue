<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxmzj33fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yxmzj33fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:copyright-solid" /></template>
