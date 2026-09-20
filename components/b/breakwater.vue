<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmrb1-6bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lmrb1-6bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:breakwater" /></template>
