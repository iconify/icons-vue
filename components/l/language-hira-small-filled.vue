<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv7ok14ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="uv7ok14ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-hira-small-filled" /></template>
