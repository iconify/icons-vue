<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrr9c8bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrr9c8bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-sketch-filled" /></template>
