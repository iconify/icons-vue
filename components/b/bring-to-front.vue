<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywxq2xbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ywxq2xbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bring-to-front" /></template>
