<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y98mjubxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y98mjubxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:desktop" /></template>
