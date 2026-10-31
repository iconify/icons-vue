<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4559ebmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4559ebmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-right-bulk-round" /></template>
