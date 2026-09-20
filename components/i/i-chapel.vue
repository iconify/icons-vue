<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow_orow8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ow_orow8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-chapel" /></template>
