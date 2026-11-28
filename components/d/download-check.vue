<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdk7-cbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdk7-cbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:download-check" /></template>
