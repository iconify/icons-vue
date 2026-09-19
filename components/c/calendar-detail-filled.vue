<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd1x97zzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd1x97zzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:calendar-detail-filled" /></template>
