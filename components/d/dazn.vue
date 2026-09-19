<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnc2a2bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bnc2a2bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:dazn" /></template>
