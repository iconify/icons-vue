<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g37t12bqh.css';
import '../../css/y/yclss2c2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g37t12bqh"/><path class="yclss2c2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:boolean-off-16" /></template>
