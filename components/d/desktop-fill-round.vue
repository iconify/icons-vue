<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc8mw0b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc8mw0b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:desktop-fill-round" /></template>
