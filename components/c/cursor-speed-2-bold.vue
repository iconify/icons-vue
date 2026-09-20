<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm0no-v2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gm0no-v2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cursor-speed-2-bold" /></template>
