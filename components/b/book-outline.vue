<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iij604fqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iij604fqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:book-outline" /></template>
