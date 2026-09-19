<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezf1yo0lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezf1yo0lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calendar-02" /></template>
