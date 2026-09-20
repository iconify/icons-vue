<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xybxuobap.css';
import '../../css/n/nu04c2bfa.css';
import '../../css/d/d490hebuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xybxuobap"/><path class="nu04c2bfa"/><path class="d490hebuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-message" /></template>
