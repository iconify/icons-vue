<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rci0tclox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rci0tclox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:city-4-filled" /></template>
