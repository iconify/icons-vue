<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1iuzd5ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1iuzd5ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-2-x" /></template>
