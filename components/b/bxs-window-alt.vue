<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3fux2b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3fux2b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-window-alt" /></template>
