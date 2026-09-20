<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu1xf2bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gu1xf2bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:magnet-solid" /></template>
