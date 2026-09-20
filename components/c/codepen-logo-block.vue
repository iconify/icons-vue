<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/titb3kk7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="titb3kk7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:codepen-logo-block" /></template>
