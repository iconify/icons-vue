<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9xtaw1ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9xtaw1ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:ellipses-horizontal-solid" /></template>
