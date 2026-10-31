<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytob4ubxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytob4ubxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:circle-dashed" /></template>
