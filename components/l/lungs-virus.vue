<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnd_fwb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cnd_fwb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:lungs-virus" /></template>
