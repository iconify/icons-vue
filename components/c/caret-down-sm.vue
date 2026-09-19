<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idbrlqb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idbrlqb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:caret-down-sm" /></template>
