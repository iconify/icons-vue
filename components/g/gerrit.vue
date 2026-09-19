<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1xw60tnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c1xw60tnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:gerrit" /></template>
