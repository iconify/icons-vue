<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0muqgbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d0muqgbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:book3" /></template>
