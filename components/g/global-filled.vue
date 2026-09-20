<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx93x9b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx93x9b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:global-filled" /></template>
