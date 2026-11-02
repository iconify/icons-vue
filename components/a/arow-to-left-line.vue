<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leb2xdbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leb2xdbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arow-to-left-line" /></template>
