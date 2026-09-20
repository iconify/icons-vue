<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lac0wjbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="lac0wjbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:intransit" /></template>
