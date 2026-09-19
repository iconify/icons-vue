<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqr_gccre.css';
import '../../css/q/q6az9ltax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b lqr_gccre"/><path class="b q6az9ltax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:groceries" /></template>
