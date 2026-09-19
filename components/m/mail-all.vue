<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzw5cbb6b.css';
import '../../css/o/o90l0ebko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zzw5cbb6b"/><path class="o90l0ebko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mail-all" /></template>
