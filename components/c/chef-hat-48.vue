<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr0p19bkd.css';
import '../../css/z/zfxhzybhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zr0p19bkd"/><path class="zfxhzybhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chef-hat-48" /></template>
