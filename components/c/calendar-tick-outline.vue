<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q44kfrbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q44kfrbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:calendar-tick-outline" /></template>
