<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loeg6il_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loeg6il_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:filter" /></template>
