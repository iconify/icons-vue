<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djqkv3dft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djqkv3dft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chat-circle-check" /></template>
