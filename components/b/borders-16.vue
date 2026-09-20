<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qndn4-bth.css';
import '../../css/j/jodh5db0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qndn4-bth"/><path clip-rule="evenodd" class="jodh5db0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:borders-16" /></template>
