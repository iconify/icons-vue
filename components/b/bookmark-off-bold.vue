<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z183d_i5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z183d_i5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-off-bold" /></template>
