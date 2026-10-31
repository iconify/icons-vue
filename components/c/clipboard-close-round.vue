<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au0fbxb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au0fbxb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-close-round" /></template>
