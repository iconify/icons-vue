<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ditspb6yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ditspb6yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ice-cream-1-solid" /></template>
