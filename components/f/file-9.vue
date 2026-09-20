<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt9rs6yuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zt9rs6yuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:file-9" /></template>
