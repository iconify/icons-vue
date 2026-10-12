<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud2z5r7ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ud2z5r7ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-play-filled" /></template>
