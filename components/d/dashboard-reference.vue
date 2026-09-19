<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f11294w7f.css';
import '../../css/c/c6vxn_-6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f11294w7f"/><path class="c6vxn_-6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:dashboard-reference" /></template>
