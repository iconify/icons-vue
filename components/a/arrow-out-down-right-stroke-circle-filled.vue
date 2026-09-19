<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6ingvywc.css';
import '../../css/n/n6_fg-lkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6ingvywc"/><path class="n6_fg-lkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-right-stroke-circle-filled" /></template>
