<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdf6hiznz.css';
import '../../css/v/vnfkbkbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zdf6hiznz"/><path class="vnfkbkbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:diamond-outline" /></template>
