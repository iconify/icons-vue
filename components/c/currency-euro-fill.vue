<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpfw86bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpfw86bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-euro-fill" /></template>
