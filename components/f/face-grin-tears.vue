<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe5k7yzpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fe5k7yzpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:face-grin-tears" /></template>
