<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpaz5wbyo.css';
import '../../css/g/gzgo2kxbo.css';
import '../../css/b/bvp6t7ksm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qpaz5wbyo"/><path class="gzgo2kxbo"/><path class="bvp6t7ksm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chassis-ground-20" /></template>
