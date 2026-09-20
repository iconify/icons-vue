<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwhnshbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwhnshbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:collapse" /></template>
