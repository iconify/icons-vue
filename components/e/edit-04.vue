<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qokuvh32r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qokuvh32r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:edit-04" /></template>
