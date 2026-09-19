<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxq0p3_iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zxq0p3_iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bless" /></template>
