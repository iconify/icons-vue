<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf571mxrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rf571mxrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:lamp-alt" /></template>
