<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shdo169pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="shdo169pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:alert" /></template>
