<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlesls0ng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlesls0ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-bulk-round" /></template>
