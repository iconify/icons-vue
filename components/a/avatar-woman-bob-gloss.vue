<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qytuaib8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qytuaib8v wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-woman-bob-gloss" /></template>
