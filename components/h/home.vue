<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt1-cgxfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt1-cgxfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home" /></template>
