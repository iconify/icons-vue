<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqe-vxb7s.css';
import '../../css/f/f_uwr3bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cqe-vxb7s"/><path class="f_uwr3bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:health-card" /></template>
