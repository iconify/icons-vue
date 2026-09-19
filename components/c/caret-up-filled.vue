<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8p_cp7cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f8p_cp7cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:caret-up-filled" /></template>
