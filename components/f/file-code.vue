<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiyst2b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="wiyst2b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:file-code" /></template>
