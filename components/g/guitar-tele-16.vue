<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgv8flbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rgv8flbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:guitar-tele-16" /></template>
