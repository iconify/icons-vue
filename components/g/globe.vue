<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj7b05b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mj7b05b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:globe" /></template>
