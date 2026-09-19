<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk46n0o3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="hk46n0o3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:laptop-code" /></template>
