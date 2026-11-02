<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whx59cbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whx59cbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brief-line" /></template>
