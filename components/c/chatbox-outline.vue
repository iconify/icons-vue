<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-ygl7brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l-ygl7brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chatbox-outline" /></template>
