<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb0ly6wwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb0ly6wwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cal-com" /></template>
