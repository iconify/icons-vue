<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2c34gbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="r2c34gbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:calendar" /></template>
