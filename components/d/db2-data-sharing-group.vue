<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnpn7ob-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qnpn7ob-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:db2-data-sharing-group" /></template>
