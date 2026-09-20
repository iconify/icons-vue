<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yasmj2z1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yasmj2z1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:inbox" /></template>
