<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv128zbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv128zbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:furigana-vertical" /></template>
