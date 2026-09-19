<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbdptmbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wbdptmbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-build" /></template>
