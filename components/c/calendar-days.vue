<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqnf0qmsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqnf0qmsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendar-days" /></template>
