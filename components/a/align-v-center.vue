<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydnzcbcmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydnzcbcmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:align-v-center" /></template>
