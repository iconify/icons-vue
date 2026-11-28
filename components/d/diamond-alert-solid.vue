<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4k1qp8kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4k1qp8kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:diamond-alert-solid" /></template>
