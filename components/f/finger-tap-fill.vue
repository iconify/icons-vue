<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on-v0u84l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on-v0u84l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:finger-tap-fill" /></template>
