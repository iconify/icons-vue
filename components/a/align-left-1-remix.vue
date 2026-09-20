<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmennq3iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pmennq3iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:align-left-1-remix" /></template>
