<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj96m5m8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj96m5m8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:m5stack" /></template>
