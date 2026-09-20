<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv5sewmdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nv5sewmdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:like-1-remix" /></template>
