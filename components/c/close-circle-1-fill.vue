<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x__g1-fnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x__g1-fnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:close-circle-1-fill" /></template>
