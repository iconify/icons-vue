<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mods8hi-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mods8hi-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-sharp-fill" /></template>
