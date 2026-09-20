<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu0_6bbna.css';
import '../../css/o/obz-b-bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pu0_6bbna"/><path class="obz-b-bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:coding-apps-websites-mobile" /></template>
