<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqho9g-ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqho9g-ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:corner-right-down-outline" /></template>
