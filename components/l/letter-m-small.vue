<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xewb970xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xewb970xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-m-small" /></template>
