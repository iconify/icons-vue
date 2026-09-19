<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2s9xyjfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="f2s9xyjfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:1" /></template>
