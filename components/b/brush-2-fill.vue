<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwiktzbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwiktzbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brush-2-fill" /></template>
