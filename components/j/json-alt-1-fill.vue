<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rld69poao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rld69poao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:json-alt-1-fill" /></template>
