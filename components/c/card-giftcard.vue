<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq0na3ryh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":408};
const content = `<path class="jq0na3ryh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:card-giftcard" /></template>
