<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5mgqkkzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u5mgqkkzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-bar" /></template>
