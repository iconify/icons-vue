<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp9nkebzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jp9nkebzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:home-filled" /></template>
