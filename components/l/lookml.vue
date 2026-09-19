<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycl9gobdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":329,"height":512};
const content = `<path class="ycl9gobdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lookml" /></template>
