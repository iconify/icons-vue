<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xst-acckn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xst-acckn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:admin-site-alt3" /></template>
