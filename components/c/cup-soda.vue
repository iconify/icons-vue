<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzg4qtqlm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzg4qtqlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cup-soda" /></template>
