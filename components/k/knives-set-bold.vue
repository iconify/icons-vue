<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4kld0byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4kld0byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:knives-set-bold" /></template>
