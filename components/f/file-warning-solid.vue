<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sda09p25t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sda09p25t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-warning-solid" /></template>
