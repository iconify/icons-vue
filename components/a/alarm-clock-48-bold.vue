<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta5f1hbwd.css';
import '../../css/v/vgs6v8b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ta5f1hbwd"/><path class="vgs6v8b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alarm-clock-48-bold" /></template>
