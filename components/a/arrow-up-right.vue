<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbk5rmbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbk5rmbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-up-right" /></template>
