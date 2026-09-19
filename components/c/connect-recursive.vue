<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh6g29_8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bh6g29_8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:connect-recursive" /></template>
