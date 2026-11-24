<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6u_-l_8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6u_-l_8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:fast-forward-filled" /></template>
