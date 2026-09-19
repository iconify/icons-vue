<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onc2e3brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="onc2e3brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:android" /></template>
