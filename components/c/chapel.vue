<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6y7mcc8q.css';
import '../../css/l/lc0gopbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="l6y7mcc8q"/><path class="lc0gopbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:chapel" /></template>
