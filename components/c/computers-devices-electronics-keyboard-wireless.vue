<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzn2_3byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vzn2_3byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-keyboard-wireless" /></template>
