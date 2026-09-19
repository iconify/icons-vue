<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv4m4mbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv4m4mbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calendar-minus-01" /></template>
