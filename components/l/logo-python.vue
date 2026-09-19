<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov02yvbiu.css';
import '../../css/w/w19t2zbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ov02yvbiu"/><path class="w19t2zbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-python" /></template>
