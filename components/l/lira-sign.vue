<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sat7ci9ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="sat7ci9ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:lira-sign" /></template>
