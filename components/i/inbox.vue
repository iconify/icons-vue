<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a73lvbc1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a73lvbc1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:inbox" /></template>
