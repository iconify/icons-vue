<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j60bv-b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j60bv-b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-man-cap-gloss" /></template>
