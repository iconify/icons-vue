<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrd_c7u5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vrd_c7u5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-xls-outline" /></template>
