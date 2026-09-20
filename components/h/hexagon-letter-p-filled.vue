<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iez0y29ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iez0y29ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-p-filled" /></template>
