<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i__vh5p7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i__vh5p7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:logstash-output" /></template>
