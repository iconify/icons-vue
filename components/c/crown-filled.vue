<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya6puy14o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya6puy14o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:crown-filled" /></template>
