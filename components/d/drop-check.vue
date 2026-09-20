<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh6dfm5rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh6dfm5rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:drop-check" /></template>
