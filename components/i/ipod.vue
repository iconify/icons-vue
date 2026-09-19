<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qphc-ub_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="qphc-ub_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:ipod" /></template>
