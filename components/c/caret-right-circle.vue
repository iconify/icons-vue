<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcwzlqb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="vcwzlqb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:caret-right-circle" /></template>
