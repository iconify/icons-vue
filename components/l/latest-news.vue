<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb39_n0xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lb39_n0xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:latest-news" /></template>
