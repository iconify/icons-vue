<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoko45bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qoko45bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-small-fill-round" /></template>
