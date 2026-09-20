<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocs2_-bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocs2_-bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:blur-off" /></template>
