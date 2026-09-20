<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy-akkzdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sy-akkzdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:arrow-circle-left" /></template>
