<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngl7jtepb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ngl7jtepb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-wikidata" /></template>
