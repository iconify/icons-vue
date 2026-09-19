<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn0tdubef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn0tdubef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:indent-right" /></template>
