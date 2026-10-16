<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq8br0b3r.css';
import '../../css/e/ey4fggn5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bq8br0b3r"/><path class="ey4fggn5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-warning-20-bold" /></template>
