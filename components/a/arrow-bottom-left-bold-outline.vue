<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwxksm_9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwxksm_9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-left-bold-outline" /></template>
