<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp78fnb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp78fnb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:keyhole-square-full" /></template>
