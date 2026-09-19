<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd_gmhbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xd_gmhbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:flag" /></template>
