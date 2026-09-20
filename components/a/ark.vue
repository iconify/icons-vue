<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awad12bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awad12bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ark" /></template>
