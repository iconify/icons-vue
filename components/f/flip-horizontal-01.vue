<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uev9vcctv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uev9vcctv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:flip-horizontal-01" /></template>
