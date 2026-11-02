<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz0n7hbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz0n7hbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:large-arrow-right-fill" /></template>
