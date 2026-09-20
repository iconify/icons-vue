<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0a_qlbll.css';
import '../../css/y/y_9gtc1-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l0a_qlbll"/><path class="y_9gtc1-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:coding-apps-websites-plugin" /></template>
