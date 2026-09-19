<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwaiq652o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rwaiq652o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:chevron-up-med" /></template>
