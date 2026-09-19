<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scu44gudw.css';
import '../../css/z/zfka66bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="scu44gudw"/><path class="zfka66bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:left-up2" /></template>
