<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyuy5z9fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyuy5z9fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:glass-water-solid" /></template>
