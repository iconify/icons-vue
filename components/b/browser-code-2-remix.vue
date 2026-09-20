<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcd4puj4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pcd4puj4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:browser-code-2-remix" /></template>
