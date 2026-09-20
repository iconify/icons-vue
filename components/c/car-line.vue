<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j09di39bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j09di39bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:car-line" /></template>
