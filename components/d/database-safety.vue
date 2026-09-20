<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2_r3-b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2_r3-b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:database-safety" /></template>
