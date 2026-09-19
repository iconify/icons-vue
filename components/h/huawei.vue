<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_bdywbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g_bdywbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:huawei" /></template>
