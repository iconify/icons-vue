<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvtoirlxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvtoirlxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-off-outline" /></template>
