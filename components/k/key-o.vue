<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eurq1d2or.css';
import '../../css/t/tav9lxblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eurq1d2or"/><path class="tav9lxblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:key-o" /></template>
