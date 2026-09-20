<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjydinbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gjydinbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grin-squint-solid" /></template>
