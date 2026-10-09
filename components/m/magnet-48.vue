<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gll0cba2f.css';
import '../../css/z/zmxd02b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gll0cba2f"/><path class="zmxd02b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:magnet-48" /></template>
