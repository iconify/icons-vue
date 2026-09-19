<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8t7ilbin.css';
import '../../css/n/nxzuucrxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l8t7ilbin"/><path class="nxzuucrxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:baffled2" /></template>
