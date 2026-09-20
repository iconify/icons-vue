<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftic40bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftic40bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gmx" /></template>
