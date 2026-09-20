<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jawcotb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jawcotb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:command" /></template>
