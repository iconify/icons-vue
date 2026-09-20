<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aznt7d64g.css';
import '../../css/l/ld_h86szq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aznt7d64g"/><path class="ld_h86szq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:image-search-filled" /></template>
