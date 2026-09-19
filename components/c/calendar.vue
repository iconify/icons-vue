<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjqfd10ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zjqfd10ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:calendar" /></template>
