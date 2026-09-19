<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xffjfs7fd.css';
import '../../css/l/ldwjonb-f.css';
import '../../css/q/q0e0esbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xffjfs7fd"/><path class="ldwjonb-f"/><path class="q0e0esbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:image-store-local" /></template>
