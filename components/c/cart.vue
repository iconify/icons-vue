<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsglcjabq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":720,"height":820};
const content = `<path class="dsglcjabq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:cart" /></template>
