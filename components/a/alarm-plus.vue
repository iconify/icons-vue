<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y95p8j6km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y95p8j6km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:alarm-plus" /></template>
