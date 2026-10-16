<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvn-b1bgm.css';
import '../../css/x/xszy37jky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jvn-b1bgm"/><path class="xszy37jky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-detector-48" /></template>
