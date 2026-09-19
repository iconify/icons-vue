<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mud3cttoi.css';
import '../../css/s/szy9kghqd.css';
import '../../css/f/favr_3e4j.css';
import '../../css/h/hfjw3s3ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mud3cttoi"/><path class="szy9kghqd"/><path class="favr_3e4j"/><path class="hfjw3s3ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:file-tray-stacked-outline" /></template>
