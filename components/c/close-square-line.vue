<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbanj-ttg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbanj-ttg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:close-square-line" /></template>
