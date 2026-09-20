<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm8lu6lmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm8lu6lmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-import-outline" /></template>
