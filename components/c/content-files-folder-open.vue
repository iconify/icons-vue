<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsldmpb3s.css';
import '../../css/f/f9o_g2bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xsldmpb3s"/><path class="f9o_g2bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:content-files-folder-open" /></template>
