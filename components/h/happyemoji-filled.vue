<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0v3-lpsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0v3-lpsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:happyemoji-filled" /></template>
