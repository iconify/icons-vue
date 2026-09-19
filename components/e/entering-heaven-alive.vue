<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy1kzqb5s.css';
import '../../css/b/bgsh7qxku.css';
import '../../css/k/k4oa-tklo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oy1kzqb5s"/><path class="bgsh7qxku"/><path class="k4oa-tklo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:entering-heaven-alive" /></template>
