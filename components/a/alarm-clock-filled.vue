<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngx1zebbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ngx1zebbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:alarm-clock-filled" /></template>
