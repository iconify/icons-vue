<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osb4_j5yq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="osb4_j5yq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:franca" /></template>
