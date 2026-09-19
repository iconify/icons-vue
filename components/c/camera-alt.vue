<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va7_sv_vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="va7_sv_vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:camera-alt" /></template>
