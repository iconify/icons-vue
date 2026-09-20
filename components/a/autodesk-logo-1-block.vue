<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3vz8ibep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3vz8ibep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:autodesk-logo-1-block" /></template>
