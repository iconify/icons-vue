<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv1b35xpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv1b35xpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calendar-edit-filled" /></template>
