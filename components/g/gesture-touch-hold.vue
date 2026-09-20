<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0u3el_yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0u3el_yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gesture-touch-hold" /></template>
