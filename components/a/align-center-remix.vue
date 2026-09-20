<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdjf7db0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fdjf7db0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:align-center-remix" /></template>
