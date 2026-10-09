<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_kcw3bme.css';
import '../../css/w/wwc-vlvua.css';
import '../../css/q/qt4fsrbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l_kcw3bme"/><path class="wwc-vlvua"/><path class="qt4fsrbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-boiler-48" /></template>
