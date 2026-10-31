<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgme0g3dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgme0g3dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-left-bulk-round" /></template>
