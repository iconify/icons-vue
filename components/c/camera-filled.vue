<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x89aj3bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x89aj3bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:camera-filled" /></template>
