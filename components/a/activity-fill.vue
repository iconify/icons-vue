<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr76i0hug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr76i0hug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:activity-fill" /></template>
