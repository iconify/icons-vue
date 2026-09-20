<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo9hubbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mo9hubbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ai-folder-robot-remix" /></template>
