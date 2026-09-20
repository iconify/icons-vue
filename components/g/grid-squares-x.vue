<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax6akkbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax6akkbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-squares-x" /></template>
