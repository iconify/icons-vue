<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgpkd5u5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgpkd5u5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-bar-down-filled" /></template>
