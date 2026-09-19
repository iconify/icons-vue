<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwl_1uwuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwl_1uwuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-down-05" /></template>
