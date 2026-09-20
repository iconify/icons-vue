<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqa8nxvxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kqa8nxvxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:m3u-editor-light" /></template>
