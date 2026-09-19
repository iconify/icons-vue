<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh8r88dml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yh8r88dml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-dizzy" /></template>
