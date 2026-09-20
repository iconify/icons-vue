<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us2i0vbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us2i0vbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:drugs-cannabis-bold" /></template>
