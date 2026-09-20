<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irhi5ow4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irhi5ow4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:brick-wall" /></template>
