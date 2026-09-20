<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz4810o9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz4810o9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-left-fill" /></template>
