<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-db1vorj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-db1vorj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-blank-line" /></template>
