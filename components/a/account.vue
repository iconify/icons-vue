<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eydmnmr0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eydmnmr0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:account" /></template>
