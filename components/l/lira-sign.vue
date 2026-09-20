<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crw-psynl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="crw-psynl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:lira-sign" /></template>
