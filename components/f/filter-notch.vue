<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvgqtcb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tvgqtcb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:filter-notch" /></template>
