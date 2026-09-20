<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvrc9db1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zvrc9db1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-avi-outline" /></template>
