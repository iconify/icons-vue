<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0ox3b4ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="f0ox3b4ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:handshake-slash" /></template>
