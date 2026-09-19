<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljn1lbc5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljn1lbc5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calendar-remove-01" /></template>
