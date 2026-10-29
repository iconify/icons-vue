<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku12kqght.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku12kqght"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:life-buoy-solid" /></template>
