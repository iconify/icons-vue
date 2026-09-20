<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqnube9ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqnube9ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:backpack-line" /></template>
