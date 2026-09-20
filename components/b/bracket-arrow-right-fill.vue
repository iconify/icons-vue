<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz7me76fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz7me76fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bracket-arrow-right-fill" /></template>
