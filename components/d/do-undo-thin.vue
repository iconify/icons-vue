<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vupb9bbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vupb9bbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:do-undo-thin" /></template>
