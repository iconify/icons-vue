<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brc5an_7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brc5an_7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:left-small-line" /></template>
