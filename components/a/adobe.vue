<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inxc_cc_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="inxc_cc_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:adobe" /></template>
