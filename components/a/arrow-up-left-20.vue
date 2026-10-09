<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hehatfcph.css';
import '../../css/a/ayea-y_zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hehatfcph"/><path class="ayea-y_zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-left-20" /></template>
