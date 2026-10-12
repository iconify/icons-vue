<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqboyjbcd.css';
import '../../css/k/ktpj8ab8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bqboyjbcd"/><path class="ktpj8ab8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:function-48" /></template>
