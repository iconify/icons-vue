<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adzo3xbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adzo3xbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:crypto" /></template>
