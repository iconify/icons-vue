<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbkbqr1mk.css';
import '../../css/h/h-szocp3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bbkbqr1mk"/><path class="h-szocp3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-switch-off" /></template>
