<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3f8adbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3f8adbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-u-filled" /></template>
