<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdz3fbi0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="kdz3fbi0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:lightbulb" /></template>
