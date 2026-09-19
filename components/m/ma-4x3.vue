<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g74m3rybx.css';
import '../../css/c/cm4vl7bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="g74m3rybx"/><path class="cm4vl7bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ma-4x3" /></template>
