<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptgr-wbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ptgr-wbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:gold-solid" /></template>
