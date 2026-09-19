<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtvcw1bvs.css';
import '../../css/w/w8cjmh64r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtvcw1bvs"/><path class="w8cjmh64r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-graduation" /></template>
