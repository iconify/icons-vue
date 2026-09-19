<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kueoalb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="kueoalb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:folder-star" /></template>
