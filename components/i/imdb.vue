<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce2-lqbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce2-lqbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:imdb" /></template>
