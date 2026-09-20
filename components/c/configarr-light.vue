<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqy7gsnam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tqy7gsnam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:configarr-light" /></template>
