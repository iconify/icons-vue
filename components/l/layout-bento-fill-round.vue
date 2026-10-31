<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb2cdnyjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb2cdnyjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:layout-bento-fill-round" /></template>
