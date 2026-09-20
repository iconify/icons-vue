<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz5lv6nih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz5lv6nih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:content-typing-machine-1-bold" /></template>
