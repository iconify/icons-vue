<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3zwvqbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u3zwvqbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:link-disconnected-bold" /></template>
