<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf4-3lbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cf4-3lbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-information" /></template>
