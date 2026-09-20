<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-hxbz97p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-hxbz97p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-half-2-filled" /></template>
