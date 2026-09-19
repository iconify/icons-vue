<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq-7wqb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq-7wqb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:join-round" /></template>
