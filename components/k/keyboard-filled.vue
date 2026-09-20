<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktlnqtbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ktlnqtbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:keyboard-filled" /></template>
