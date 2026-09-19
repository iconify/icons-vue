<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_lpopb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d_lpopb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gams" /></template>
