<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqlox3zgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqlox3zgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:loka" /></template>
