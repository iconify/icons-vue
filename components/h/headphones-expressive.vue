<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6e34ibbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s6e34ibbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:headphones-expressive" /></template>
