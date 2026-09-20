<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymf0v_b9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymf0v_b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:business-big-small-fish-bold" /></template>
