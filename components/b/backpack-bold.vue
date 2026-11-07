<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_f_qcc_q.css';
import '../../css/l/lp0dbjbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x_f_qcc_q"/><path class="lp0dbjbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:backpack-bold" /></template>
