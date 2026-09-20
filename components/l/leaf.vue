<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thd_9hsjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thd_9hsjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:leaf" /></template>
