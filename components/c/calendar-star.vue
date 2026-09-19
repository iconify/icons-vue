<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngqxn8bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngqxn8bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:calendar-star" /></template>
