<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cret2ebde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cret2ebde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendar-x" /></template>
