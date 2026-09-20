<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcgmqt-xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mcgmqt-xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:headphones-sound" /></template>
