<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us3dk9lkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us3dk9lkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:egg-gloss" /></template>
