<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzu6dufxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzu6dufxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:calendar-alt" /></template>
