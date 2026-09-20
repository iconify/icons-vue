<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wylb8db_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wylb8db_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:arrow-previous-ltr" /></template>
