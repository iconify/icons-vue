<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5j902m7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5j902m7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eye-off-line" /></template>
