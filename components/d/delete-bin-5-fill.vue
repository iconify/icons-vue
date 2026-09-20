<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzswrybfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzswrybfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:delete-bin-5-fill" /></template>
