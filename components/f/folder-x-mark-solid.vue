<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf1inpknb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yf1inpknb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-x-mark-solid" /></template>
