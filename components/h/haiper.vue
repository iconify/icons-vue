<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wixg6xxac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wixg6xxac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:haiper" /></template>
