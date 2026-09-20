<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpg7efb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpg7efb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hotwire" /></template>
