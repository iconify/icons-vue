<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hko6ldm5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hko6ldm5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:left-fill" /></template>
