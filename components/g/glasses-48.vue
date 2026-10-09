<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4df3nkws.css';
import '../../css/j/jt1aqlbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4df3nkws"/><path class="jt1aqlbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:glasses-48" /></template>
