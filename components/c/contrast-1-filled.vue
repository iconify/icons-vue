<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqvxq3bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqvxq3bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:contrast-1-filled" /></template>
