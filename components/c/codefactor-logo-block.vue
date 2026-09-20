<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6_1xzbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b6_1xzbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:codefactor-logo-block" /></template>
