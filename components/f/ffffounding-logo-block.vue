<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phd1g1bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="phd1g1bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:ffffounding-logo-block" /></template>
