<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdos38jip.css';
import '../../css/p/p1kcgj3tk.css';
import '../../css/y/ywhth4bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pdos38jip"/><path class="p1kcgj3tk"/><path class="ywhth4bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-plus-48-bold" /></template>
