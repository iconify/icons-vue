<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egt7e-0qv.css';
import '../../css/z/z2q2hdbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="egt7e-0qv"/><path class="z2q2hdbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:column-delete" /></template>
