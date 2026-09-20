<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omcmqybsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="omcmqybsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:file-prescription-solid" /></template>
