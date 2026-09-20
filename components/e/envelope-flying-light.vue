<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6nvqp9jz.css';
import '../../css/t/tynapsbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6nvqp9jz"/><path class="tynapsbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:envelope-flying-light" /></template>
