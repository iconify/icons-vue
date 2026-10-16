<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsv726byj.css';
import '../../css/w/w0t6-kbpw.css';
import '../../css/v/ve_svj3jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tsv726byj"/><path class="w0t6-kbpw"/><path class="ve_svj3jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:iot-device-20-bold" /></template>
