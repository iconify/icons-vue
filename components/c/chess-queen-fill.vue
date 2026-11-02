<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8dbjrn2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8dbjrn2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chess-queen-fill" /></template>
