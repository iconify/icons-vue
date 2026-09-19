<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlqaccc_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hlqaccc_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:hackerearth" /></template>
