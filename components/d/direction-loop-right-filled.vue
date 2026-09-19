<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrvbtsb1t.css';
import '../../css/x/x5brej6ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yrvbtsb1t"/><path class="x5brej6ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-loop-right-filled" /></template>
