<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiwpj83ce.css';
import '../../css/h/h9e4f9v-u.css';
import '../../css/l/ln0tkebwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xiwpj83ce"/><path class="h9e4f9v-u"/><path class="ln0tkebwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:green-bond-20" /></template>
