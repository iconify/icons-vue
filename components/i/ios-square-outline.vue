<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa-h57bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xa-h57bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-square-outline" /></template>
