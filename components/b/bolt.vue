<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj50_i5oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj50_i5oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bolt" /></template>
