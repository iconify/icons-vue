<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwh29wbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="xwh29wbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:2" /></template>
