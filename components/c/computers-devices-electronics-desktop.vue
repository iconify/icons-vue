<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3e1967if.css';
import '../../css/f/f9s06tb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c3e1967if"/><path class="f9s06tb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-desktop" /></template>
