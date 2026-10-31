<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc2cd4bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc2cd4bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-plus-corner-round" /></template>
