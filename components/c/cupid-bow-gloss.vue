<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkkp9mbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkkp9mbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cupid-bow-gloss" /></template>
