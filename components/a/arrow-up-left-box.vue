<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftz4bxa2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ftz4bxa2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-up-left-box" /></template>
