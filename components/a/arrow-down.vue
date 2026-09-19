<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpwpfybnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpwpfybnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-down" /></template>
