<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw2n_kb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aw2n_kb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-set" /></template>
