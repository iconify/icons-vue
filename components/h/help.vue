<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2g9ulz4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2g9ulz4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:help" /></template>
