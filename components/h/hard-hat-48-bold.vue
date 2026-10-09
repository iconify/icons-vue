<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w010_tghd.css';
import '../../css/j/jjy_43hmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w010_tghd"/><path class="jjy_43hmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hard-hat-48-bold" /></template>
