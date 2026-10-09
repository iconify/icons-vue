<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s71x42bul.css';
import '../../css/d/dutsueb3v.css';
import '../../css/y/ybedvpc_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s71x42bul"/><path class="dutsueb3v"/><path class="ybedvpc_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:jack-up-vessel-20-bold" /></template>
