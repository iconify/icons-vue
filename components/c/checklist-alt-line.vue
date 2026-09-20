<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd6rmkbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd6rmkbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:checklist-alt-line" /></template>
