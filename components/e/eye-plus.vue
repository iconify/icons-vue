<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eziq8xbrj.css';
import '../../css/s/sb7vsacsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eziq8xbrj"/><path class="sb7vsacsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:eye-plus" /></template>
