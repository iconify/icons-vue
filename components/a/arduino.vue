<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nunux4e-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nunux4e-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:arduino" /></template>
