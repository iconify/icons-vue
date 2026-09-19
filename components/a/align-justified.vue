<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2l0cwc7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":448};
const content = `<path class="p2l0cwc7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:align-justified" /></template>
