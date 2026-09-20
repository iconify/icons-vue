<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu1ua8bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu1ua8bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:curseforge" /></template>
