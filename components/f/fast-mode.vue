<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwel8ob0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="cwel8ob0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:fast-mode" /></template>
