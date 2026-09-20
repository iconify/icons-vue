<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk_5x50tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk_5x50tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:elixir" /></template>
