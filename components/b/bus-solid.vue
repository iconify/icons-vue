<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzm2qigte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzm2qigte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bus-solid" /></template>
