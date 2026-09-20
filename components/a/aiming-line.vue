<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv4va0_8o.css';
import '../../css/l/lf01q5b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv4va0_8o"/><path class="lf01q5b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aiming-line" /></template>
