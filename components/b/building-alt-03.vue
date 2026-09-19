<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu4velb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fu4velb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:building-alt-03" /></template>
