<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujr83xbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujr83xbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airbag" /></template>
