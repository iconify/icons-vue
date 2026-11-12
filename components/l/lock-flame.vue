<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj7fwkbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj7fwkbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lock-flame" /></template>
