<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7rwwgb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w7rwwgb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:3d-scale-remix" /></template>
