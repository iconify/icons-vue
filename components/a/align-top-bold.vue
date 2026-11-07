<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nelsscpmr.css';
import '../../css/f/fx2vq-b3e.css';
import '../../css/r/r5hjnw2io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nelsscpmr"/><path class="fx2vq-b3e"/><path class="r5hjnw2io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-top-bold" /></template>
