<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjcl_bc7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qjcl_bc7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:app-store" /></template>
