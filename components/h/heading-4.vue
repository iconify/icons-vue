<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yifcz_b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yifcz_b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading-4" /></template>
