<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhxk_vbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lhxk_vbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:double-check" /></template>
