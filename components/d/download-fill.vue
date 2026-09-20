<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9d0thx6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9d0thx6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:download-fill" /></template>
