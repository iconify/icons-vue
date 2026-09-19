<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp7dyqbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sp7dyqbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:d3" /></template>
