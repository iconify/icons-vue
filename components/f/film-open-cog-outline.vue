<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upk2mwbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upk2mwbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:film-open-cog-outline" /></template>
