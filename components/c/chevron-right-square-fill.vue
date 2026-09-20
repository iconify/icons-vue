<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxb0617gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fxb0617gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:chevron-right-square-fill" /></template>
