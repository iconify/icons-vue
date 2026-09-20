<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-1ma8skb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-1ma8skb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hand-sanitizer-fill" /></template>
