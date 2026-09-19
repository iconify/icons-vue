<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8uegvv_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="t8uegvv_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:file-lines" /></template>
