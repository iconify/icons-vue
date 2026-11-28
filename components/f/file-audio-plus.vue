<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu9zylbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu9zylbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-audio-plus" /></template>
