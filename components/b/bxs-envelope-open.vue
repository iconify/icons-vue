<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwusq4bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwusq4bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-envelope-open" /></template>
