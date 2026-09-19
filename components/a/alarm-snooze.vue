<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4uk8wrue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="h4uk8wrue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:alarm-snooze" /></template>
