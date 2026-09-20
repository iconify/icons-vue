<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkuijcbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bkuijcbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-learning-light" /></template>
