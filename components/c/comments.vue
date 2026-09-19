<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgeh2rblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":634};
const content = `<path class="wgeh2rblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:comments" /></template>
