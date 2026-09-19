<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8sjw-c0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f8sjw-c0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:expanded-rays" /></template>
