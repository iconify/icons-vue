<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3pvx_84m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="h3pvx_84m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:location" /></template>
