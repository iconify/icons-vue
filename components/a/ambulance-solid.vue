<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg2nftvpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zg2nftvpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ambulance-solid" /></template>
