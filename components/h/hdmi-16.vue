<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpr1pgalx.css';
import '../../css/o/ov5vkel-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kpr1pgalx"/><path clip-rule="evenodd" class="ov5vkel-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:hdmi-16" /></template>
