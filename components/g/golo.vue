<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypx0rvnvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ypx0rvnvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:golo" /></template>
