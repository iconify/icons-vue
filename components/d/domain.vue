<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ail75ac-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ail75ac-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:domain" /></template>
