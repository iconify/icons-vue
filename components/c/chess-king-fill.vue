<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq21djx9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq21djx9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chess-king-fill" /></template>
