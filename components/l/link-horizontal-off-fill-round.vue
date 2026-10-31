<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aapds4maj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aapds4maj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-horizontal-off-fill-round" /></template>
