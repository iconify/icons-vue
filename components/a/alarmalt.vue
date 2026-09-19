<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob0egjsku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="ob0egjsku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:alarmalt" /></template>
