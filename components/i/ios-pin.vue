<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hane4bbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hane4bbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-pin" /></template>
