<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl0efihro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xl0efihro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-share-alt" /></template>
