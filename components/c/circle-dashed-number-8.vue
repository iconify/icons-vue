<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpcu_5bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpcu_5bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-number-8" /></template>
