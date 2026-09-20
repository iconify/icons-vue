<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f00jo0q8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f00jo0q8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dog-side-off" /></template>
