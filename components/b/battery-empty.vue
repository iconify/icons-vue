<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqijwxb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oqijwxb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:battery-empty" /></template>
