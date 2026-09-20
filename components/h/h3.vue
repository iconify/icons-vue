<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opy_qdyex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opy_qdyex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:h3" /></template>
