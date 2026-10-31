<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etaokrw9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etaokrw9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calendar-days-gloss" /></template>
