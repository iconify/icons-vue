<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjo5o7goe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tjo5o7goe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:box-ipc" /></template>
