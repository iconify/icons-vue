<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p93f7gb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p93f7gb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:color-palette-bold" /></template>
