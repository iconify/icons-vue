<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqxr__w0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqxr__w0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chess-bishop-fill" /></template>
