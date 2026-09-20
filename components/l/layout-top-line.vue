<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aai67211g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aai67211g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-top-line" /></template>
