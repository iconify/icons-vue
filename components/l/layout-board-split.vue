<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll_87xwpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll_87xwpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-board-split" /></template>
