<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piz_jmb7s.css';
import '../../css/z/zs8x37yqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="piz_jmb7s"/><path class="zs8x37yqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chat-add-16" /></template>
