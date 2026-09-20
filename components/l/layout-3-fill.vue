<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sht7gzb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sht7gzb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-3-fill" /></template>
