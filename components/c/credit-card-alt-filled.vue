<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipjz1gbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipjz1gbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-alt-filled" /></template>
