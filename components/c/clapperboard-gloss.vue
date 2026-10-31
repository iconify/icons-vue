<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv3zmlbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv3zmlbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clapperboard-gloss" /></template>
