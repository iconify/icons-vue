<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w76dcob_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w76dcob_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:increase-indent" /></template>
