<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsddpbybl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsddpbybl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:cursor-arrow-ripple" /></template>
