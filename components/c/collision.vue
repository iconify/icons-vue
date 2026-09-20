<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-c1zgbnj.css';
import '../../css/a/amusoxbhb.css';
import '../../css/s/serii-led.css';
import '../../css/c/cuarf-7ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i-c1zgbnj"/><path class="amusoxbhb"/><path class="serii-led"/><path class="cuarf-7ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:collision" /></template>
