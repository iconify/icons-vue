<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4503eb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4503eb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-fast-forward-circle" /></template>
