<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyfszws3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="kyfszws3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:download-circle" /></template>
