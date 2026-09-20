<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4g5wbp8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4g5wbp8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up2" /></template>
