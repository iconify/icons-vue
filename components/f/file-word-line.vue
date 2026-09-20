<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt7vg02ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt7vg02ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-word-line" /></template>
