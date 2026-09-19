<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcmqf6bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":680};
const content = `<path class="jcmqf6bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:dailycalendar" /></template>
