<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex9s0kk5d.css';
import '../../css/a/a_7jv01nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="ex9s0kk5d"/><path class="a_7jv01nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:albania" /></template>
