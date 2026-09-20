<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc013ab-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc013ab-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lemon-squeezy-line" /></template>
