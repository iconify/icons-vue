<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-cj6-fya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-cj6-fya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fold-horizontal-fill" /></template>
