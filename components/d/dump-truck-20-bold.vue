<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkgj9ib4r.css';
import '../../css/x/x1b3r-bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bkgj9ib4r"/><path class="x1b3r-bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dump-truck-20-bold" /></template>
