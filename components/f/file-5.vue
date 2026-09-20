<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks1yeixst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ks1yeixst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:file-5" /></template>
