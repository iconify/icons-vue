<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf2kxdbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sf2kxdbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-square" /></template>
