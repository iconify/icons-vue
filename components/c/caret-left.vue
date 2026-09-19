<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj56_ebdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mj56_ebdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:caret-left" /></template>
