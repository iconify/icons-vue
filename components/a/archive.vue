<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzi8fwb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzi8fwb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:archive" /></template>
