<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh5lwhb7v.css';
import '../../css/g/gyt736dji.css';
import '../../css/h/hua3e5bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bh5lwhb7v"/><path class="gyt736dji"/><path class="hua3e5bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:laser-level-48-bold" /></template>
