<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu5eqibwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fu5eqibwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bbc-iplayer-logo-2-block" /></template>
