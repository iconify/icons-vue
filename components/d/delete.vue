<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwbs4bb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":512};
const content = `<path class="xwbs4bb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:delete" /></template>
