<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh_wv8bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh_wv8bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:egg-fried-filled" /></template>
