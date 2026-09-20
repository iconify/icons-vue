<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7pi4cqiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7pi4cqiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:asset-filled" /></template>
