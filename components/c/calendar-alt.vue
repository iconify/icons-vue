<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i10-u0blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="i10-u0blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:calendar-alt" /></template>
