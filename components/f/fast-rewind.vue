<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqvt6ac-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":376,"height":384};
const content = `<path class="cqvt6ac-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:fast-rewind" /></template>
