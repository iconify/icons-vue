<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7v0wg4bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7v0wg4bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-line" /></template>
