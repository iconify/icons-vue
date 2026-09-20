<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t541ctb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t541ctb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:500px" /></template>
