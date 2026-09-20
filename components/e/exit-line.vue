<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifvsw0btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifvsw0btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exit-line" /></template>
