<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag6dbfbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ag6dbfbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:hydrogen-bold" /></template>
