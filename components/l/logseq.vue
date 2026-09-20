<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq7w7gbnw.css';
import '../../css/d/dm_tx1bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fq7w7gbnw"/><path class="dm_tx1bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:logseq" /></template>
