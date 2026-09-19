<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o786i_bpn.css';
import '../../css/w/w_5dyix0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o786i_bpn"/><path class="w_5dyix0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flight-international" /></template>
