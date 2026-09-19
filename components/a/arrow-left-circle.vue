<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad3vngbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad3vngbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-left-circle" /></template>
