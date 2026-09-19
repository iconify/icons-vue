<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w252twlik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w252twlik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-dizzy" /></template>
