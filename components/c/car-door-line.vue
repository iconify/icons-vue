<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhgbnmpww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhgbnmpww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:car-door-line" /></template>
