<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro8s8ib8b.css';
import '../../css/t/terfpnntt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ro8s8ib8b"/><path class="terfpnntt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:employee-line" /></template>
