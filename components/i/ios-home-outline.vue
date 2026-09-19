<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmbmz2bey.css';
import '../../css/h/h4npctbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tmbmz2bey"/><path class="h4npctbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-home-outline" /></template>
