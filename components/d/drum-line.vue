<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdn7-dr4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdn7-dr4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drum-line" /></template>
