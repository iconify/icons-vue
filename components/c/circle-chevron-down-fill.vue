<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z48rm97-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z48rm97-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:circle-chevron-down-fill" /></template>
