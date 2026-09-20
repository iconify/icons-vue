<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfwtrcgys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dfwtrcgys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:3d-move-solid" /></template>
