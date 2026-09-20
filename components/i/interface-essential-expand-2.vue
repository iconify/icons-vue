<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b40784e-u.css';
import '../../css/g/g7_--dwga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b40784e-u"/><path class="g7_--dwga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-expand-2" /></template>
