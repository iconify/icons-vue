<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qae_zubij.css';
import '../../css/s/stlnhm10c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qae_zubij"/><path class="stlnhm10c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fish-ladder-20" /></template>
