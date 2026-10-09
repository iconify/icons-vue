<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry85_ib5t.css';
import '../../css/g/g7joh4_lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ry85_ib5t"/><path class="g7joh4_lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flag-48" /></template>
