<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlkvb9b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlkvb9b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:align-horizontal-solid" /></template>
