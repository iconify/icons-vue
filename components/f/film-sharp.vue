<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atd8x-w7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atd8x-w7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:film-sharp" /></template>
