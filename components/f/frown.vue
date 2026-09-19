<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp_oc9q1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zp_oc9q1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:frown" /></template>
