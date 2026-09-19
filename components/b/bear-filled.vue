<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8yo2xlul.css';
import '../../css/w/wth0vybwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8yo2xlul"/><path class="wth0vybwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bear-filled" /></template>
