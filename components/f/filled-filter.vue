<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfmav5c8a.css';
import '../../css/k/k1fidk1yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jfmav5c8a"/><path class="k1fidk1yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:filled-filter" /></template>
