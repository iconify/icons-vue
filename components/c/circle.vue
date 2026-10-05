<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edcg1xozq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edcg1xozq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:circle" /></template>
