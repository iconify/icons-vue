<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2ad-mbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2ad-mbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:calendar-dollar" /></template>
