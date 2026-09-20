<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snaubdbur.css';
import '../../css/z/zh_kfpbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="snaubdbur"/><path class="zh_kfpbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frankmd-dark" /></template>
