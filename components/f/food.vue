<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlh-g9eso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlh-g9eso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:food" /></template>
