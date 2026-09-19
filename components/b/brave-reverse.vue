<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtl_iywhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jtl_iywhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:brave-reverse" /></template>
