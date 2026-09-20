<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0xf62b4y.css';
import '../../css/e/e5i6xxbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e0xf62b4y"/><path class="e5i6xxbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:gift-solid" /></template>
