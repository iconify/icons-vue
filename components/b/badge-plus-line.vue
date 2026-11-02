<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3_nkuuoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3_nkuuoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-plus-line" /></template>
