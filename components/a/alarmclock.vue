<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng3rv4n5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ng3rv4n5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:alarmclock" /></template>
