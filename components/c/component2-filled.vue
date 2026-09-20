<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc8x5ib_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc8x5ib_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:component2-filled" /></template>
