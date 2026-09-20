<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj8c_hskw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj8c_hskw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-file-outline" /></template>
