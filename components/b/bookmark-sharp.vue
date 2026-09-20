<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae4hbqbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae4hbqbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bookmark-sharp" /></template>
