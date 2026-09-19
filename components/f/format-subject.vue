<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7misdb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="n7misdb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-subject" /></template>
