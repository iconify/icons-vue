<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de0glnbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="de0glnbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:aaabattery" /></template>
