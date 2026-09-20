<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1ms6ll0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m1ms6ll0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:archive-box-arrow-up-16-solid" /></template>
