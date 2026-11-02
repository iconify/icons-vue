<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8h2s5a6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8h2s5a6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-top-line" /></template>
