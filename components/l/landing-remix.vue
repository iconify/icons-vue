<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbnj-pbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sbnj-pbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:landing-remix" /></template>
