<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwnj5k5sb.css';
import '../../css/b/b7mwlnblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":65,"height":64};
const content = `<path class="rwnj5k5sb"/><path class="b7mwlnblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ethereum" /></template>
