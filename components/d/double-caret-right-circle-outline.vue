<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neu3zkbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="neu3zkbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-right-circle-outline" /></template>
