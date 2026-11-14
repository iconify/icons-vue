<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvn4u4bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvn4u4bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:analytics-02" /></template>
