<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii82hnrhg.css';
import '../../css/l/lzpmdx6fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="ii82hnrhg"/><path class="lzpmdx6fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cloud-rain" /></template>
