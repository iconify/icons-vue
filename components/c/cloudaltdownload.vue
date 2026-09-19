<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp2mkxbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="kp2mkxbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cloudaltdownload" /></template>
