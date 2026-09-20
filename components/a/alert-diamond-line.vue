<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbj_d9baz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbj_d9baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alert-diamond-line" /></template>
