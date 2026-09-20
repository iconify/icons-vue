<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prb5lc1je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prb5lc1je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cupcake-line" /></template>
