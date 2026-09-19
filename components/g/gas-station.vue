<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysus3cbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ysus3cbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:gas-station" /></template>
