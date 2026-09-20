<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr8uoyb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr8uoyb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cog-off-outline" /></template>
