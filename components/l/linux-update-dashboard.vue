<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eisknabqx.css';
import '../../css/h/hawpsccml.css';
import '../../css/x/xg9h40s8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eisknabqx"/><path class="hawpsccml"/><path class="xg9h40s8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linux-update-dashboard" /></template>
