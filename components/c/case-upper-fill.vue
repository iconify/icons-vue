<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfh15160c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfh15160c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:case-upper-fill" /></template>
