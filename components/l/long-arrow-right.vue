<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbcloqqar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="tbcloqqar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:long-arrow-right" /></template>
