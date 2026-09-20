<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-s921btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n-s921btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:language" /></template>
