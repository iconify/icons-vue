<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz2qd0bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz2qd0bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:compass-3-line" /></template>
