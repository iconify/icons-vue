<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1qu1v53u.css';
import '../../css/u/u9c-71bvi.css';
import '../../css/v/vw_n11rmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n1qu1v53u"/><path class="u9c-71bvi"/><path class="vw_n11rmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-lock-20-bold" /></template>
