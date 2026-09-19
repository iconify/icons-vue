<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwj3tybzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwj3tybzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:logout-circle-02" /></template>
