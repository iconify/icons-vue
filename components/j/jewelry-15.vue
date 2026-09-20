<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quk-u9b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="quk-u9b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:jewelry-15" /></template>
