<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmscxibfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmscxibfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:columns-3" /></template>
