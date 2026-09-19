<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iygfuccbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iygfuccbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-send" /></template>
