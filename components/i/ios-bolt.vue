<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbt7fulfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hbt7fulfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-bolt" /></template>
