<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlibchyrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="hlibchyrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:calendar-alt" /></template>
