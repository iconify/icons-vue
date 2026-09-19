<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsrnh97vr.css';
import '../../css/k/ksctdbbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dsrnh97vr"/><path class="ksctdbbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bring-forward" /></template>
