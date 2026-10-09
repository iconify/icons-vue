<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr0clkknd.css';
import '../../css/b/bhhnh4bmp.css';
import '../../css/k/k_3z1lbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zr0clkknd"/><path class="bhhnh4bmp"/><path class="k_3z1lbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-refuelling-20" /></template>
