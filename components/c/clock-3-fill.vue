<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4ex10bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g4ex10bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-3-fill" /></template>
