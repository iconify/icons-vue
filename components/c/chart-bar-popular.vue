<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t00icf71t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t00icf71t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chart-bar-popular" /></template>
