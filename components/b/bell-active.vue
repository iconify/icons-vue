<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybiv9vb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ybiv9vb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:bell-active" /></template>
