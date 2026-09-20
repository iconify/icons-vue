<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6kt0sa7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6kt0sa7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:coffee-maker-outline" /></template>
