<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb2kvcb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb2kvcb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-bottom-left-on-square" /></template>
