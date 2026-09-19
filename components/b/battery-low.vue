<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jswgxzn3t.css';
import '../../css/u/u5z_1ibwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jswgxzn3t"/><path class="u5z_1ibwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:battery-low" /></template>
