<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht9r1ybyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht9r1ybyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-hive" /></template>
