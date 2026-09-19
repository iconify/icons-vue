<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al76bac_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":232,"height":384};
const content = `<path class="al76bac_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-bold" /></template>
