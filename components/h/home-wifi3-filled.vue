<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypalqe4ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ypalqe4ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-wifi3-filled" /></template>
