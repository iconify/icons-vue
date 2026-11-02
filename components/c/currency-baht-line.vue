<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz2t_87az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz2t_87az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-baht-line" /></template>
