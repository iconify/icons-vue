<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9n72kbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1088,"height":1664};
const content = `<path class="n9n72kbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:chevron-left" /></template>
