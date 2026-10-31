<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmksrjkpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmksrjkpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:columns-duocolor-round" /></template>
