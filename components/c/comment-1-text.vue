<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mglbirb9o.css';
import '../../css/e/eu46usfmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mglbirb9o"/><path clip-rule="evenodd" class="eu46usfmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:comment-1-text" /></template>
