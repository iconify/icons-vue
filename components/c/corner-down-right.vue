<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a25lipl2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a25lipl2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:corner-down-right" /></template>
