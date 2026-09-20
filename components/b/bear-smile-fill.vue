<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-krjcbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-krjcbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bear-smile-fill" /></template>
