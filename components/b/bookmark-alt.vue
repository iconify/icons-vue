<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbfurgbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xbfurgbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bookmark-alt" /></template>
