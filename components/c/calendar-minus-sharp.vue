<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8tssyg5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8tssyg5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-minus-sharp" /></template>
