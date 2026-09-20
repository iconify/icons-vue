<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx3mlpxzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rx3mlpxzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:keyboard-remix" /></template>
