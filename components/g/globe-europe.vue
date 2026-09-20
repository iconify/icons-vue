<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inc2gvbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="inc2gvbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:globe-europe" /></template>
