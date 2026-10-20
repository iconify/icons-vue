<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di__cabvm.css';
import '../../css/j/j8d93dwgj.css';
import '../../css/h/hxtxelb0w.css';
import '../../css/s/sqfcwibec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="di__cabvm"/><path class="j8d93dwgj"/><path class="hxtxelb0w"/><path class="sqfcwibec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:devices-48" /></template>
