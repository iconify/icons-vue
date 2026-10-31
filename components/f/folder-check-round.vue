<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cge5m7bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cge5m7bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-check-round" /></template>
