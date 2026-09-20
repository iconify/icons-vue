<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxnl73b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxnl73b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-down-right" /></template>
