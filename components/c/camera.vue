<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgvdncbht.css';
import '../../css/s/sz375c7xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dgvdncbht"/><path class="sz375c7xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:camera" /></template>
