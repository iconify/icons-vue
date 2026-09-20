<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au2dbgp3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au2dbgp3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:kakao-talk-line" /></template>
