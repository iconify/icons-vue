<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-z0xfb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="o-z0xfb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud" /></template>
