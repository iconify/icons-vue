<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gngdgwsqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gngdgwsqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:boost" /></template>
