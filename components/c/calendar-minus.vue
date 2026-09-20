<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6atg9b5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6atg9b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:calendar-minus" /></template>
