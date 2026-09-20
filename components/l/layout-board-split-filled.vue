<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppclbl6nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppclbl6nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-board-split-filled" /></template>
