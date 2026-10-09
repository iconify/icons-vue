<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hotj8abpa.css';
import '../../css/l/ls15nzj_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hotj8abpa"/><path class="ls15nzj_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alert-octagon-48" /></template>
