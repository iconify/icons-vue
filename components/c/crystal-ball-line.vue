<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bop0cmbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bop0cmbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:crystal-ball-line" /></template>
