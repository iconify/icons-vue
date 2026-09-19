<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhy_q8b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":896};
const content = `<path class="yhy_q8b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:legacyfilemanager" /></template>
