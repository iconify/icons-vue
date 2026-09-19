<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otplr3bgs.css';
import '../../css/k/kiwinsf3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="otplr3bgs"/><path class="kiwinsf3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:devices" /></template>
