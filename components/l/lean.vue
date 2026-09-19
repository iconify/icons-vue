<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_aolf-cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":315,"height":512};
const content = `<path class="l_aolf-cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lean" /></template>
