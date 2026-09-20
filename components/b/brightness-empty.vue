<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll2_3eb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll2_3eb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:brightness-empty" /></template>
