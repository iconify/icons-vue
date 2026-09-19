<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sma2sc7pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sma2sc7pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:bolt-slash" /></template>
