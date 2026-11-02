<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_ofxl4-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_ofxl4-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:corners-pointing-out" /></template>
