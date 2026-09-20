<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqm-8rbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqm-8rbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:blood-outline" /></template>
