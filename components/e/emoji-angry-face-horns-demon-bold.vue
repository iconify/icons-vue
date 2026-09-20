<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5b7hjb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o5b7hjb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:emoji-angry-face-horns-demon-bold" /></template>
