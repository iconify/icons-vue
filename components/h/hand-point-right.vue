<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs48jm-6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zs48jm-6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:hand-point-right" /></template>
