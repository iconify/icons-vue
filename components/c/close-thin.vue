<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc1dgrbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc1dgrbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:close-thin" /></template>
