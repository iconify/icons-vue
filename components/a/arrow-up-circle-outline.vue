<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpu1kzy3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zpu1kzy3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-up-circle-outline" /></template>
