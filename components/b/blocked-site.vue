<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo9mqglso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oo9mqglso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:blocked-site" /></template>
