<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_p_7zbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t_p_7zbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:check" /></template>
