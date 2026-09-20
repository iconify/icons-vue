<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmok0r2zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gmok0r2zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-password-type" /></template>
