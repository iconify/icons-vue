<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcsppmign.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcsppmign"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-dram" /></template>
