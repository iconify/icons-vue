<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb_r3_53g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yb_r3_53g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:angrycreative" /></template>
