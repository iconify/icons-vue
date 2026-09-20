<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi9pucb8a.css';
import '../../css/y/y008p5b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi9pucb8a"/><path clip-rule="evenodd" class="y008p5b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:gif-light" /></template>
