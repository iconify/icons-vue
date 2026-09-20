<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be5_n7dba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be5_n7dba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:apple-ios" /></template>
