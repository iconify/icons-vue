<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vog6-j50i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vog6-j50i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:calendar-plus" /></template>
