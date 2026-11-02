<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2i44_bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2i44_bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:banknote-arrow-down-fill" /></template>
