<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c885x9kbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c885x9kbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-up-s-fill" /></template>
