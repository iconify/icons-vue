<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl9xk542o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl9xk542o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:calendar-days" /></template>
