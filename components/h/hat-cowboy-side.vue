<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp5gdybxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="vp5gdybxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hat-cowboy-side" /></template>
