<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ara_o5b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ara_o5b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bell-line" /></template>
