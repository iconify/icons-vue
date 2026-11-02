<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8-xnn5rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8-xnn5rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lemon-squeezy-fill" /></template>
