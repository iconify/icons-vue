<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9fn-_o-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f9fn-_o-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:fireworks-rocket-remix" /></template>
