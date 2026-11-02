<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx1g2ub7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx1g2ub7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-up-wide-narrow-fill" /></template>
