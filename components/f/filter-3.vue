<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfp4zrbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfp4zrbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:filter-3" /></template>
