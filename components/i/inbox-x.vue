<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwxig2-hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwxig2-hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:inbox-x" /></template>
