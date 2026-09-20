<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw-bguxsi.css';
import '../../css/q/qx1z26mll.css';
import '../../css/e/e907rnzaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tw-bguxsi"/><path class="qx1z26mll"/><path class="e907rnzaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:coding-apps-websites-phone-tablet" /></template>
