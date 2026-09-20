<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi4a21e2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi4a21e2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bungie" /></template>
