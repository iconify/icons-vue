<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izgbbhbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izgbbhbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-plus-fill" /></template>
