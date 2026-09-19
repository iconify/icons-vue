<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbdu_8b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":416};
const content = `<path class="rbdu_8b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:blur-off" /></template>
