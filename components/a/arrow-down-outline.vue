<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmjs1io_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmjs1io_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-down-outline" /></template>
