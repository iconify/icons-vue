<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u28bdqbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u28bdqbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:delete-bookmark-solid" /></template>
