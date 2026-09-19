<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dda67et_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dda67et_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-haze2-fill" /></template>
