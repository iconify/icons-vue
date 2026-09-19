<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc7z52rjt.css';
import '../../css/v/v3vofob6e.css';
import '../../css/o/ovnqk_b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kc7z52rjt"/><path class="v3vofob6e"/><path class="ovnqk_b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-average" /></template>
