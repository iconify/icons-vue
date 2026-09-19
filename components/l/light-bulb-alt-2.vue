<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of4_u7bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b of4_u7bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:light-bulb-alt-2" /></template>
