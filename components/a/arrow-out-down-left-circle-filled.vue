<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysrry-bqw.css';
import '../../css/j/jbyiw1r0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysrry-bqw"/><path class="jbyiw1r0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-left-circle-filled" /></template>
