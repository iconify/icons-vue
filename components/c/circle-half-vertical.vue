<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weagqlbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="weagqlbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-half-vertical" /></template>
