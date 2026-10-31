<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w60dh3b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w60dh3b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:baby-bottle-gloss" /></template>
