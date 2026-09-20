<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vex5fhbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vex5fhbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:hand-rock-16" /></template>
