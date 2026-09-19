<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnqm6cc8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnqm6cc8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:calendar-month-outline" /></template>
