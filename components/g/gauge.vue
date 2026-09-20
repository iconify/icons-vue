<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd27m3bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gd27m3bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:gauge" /></template>
