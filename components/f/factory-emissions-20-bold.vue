<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzjn3zb4d.css';
import '../../css/l/li792gxac.css';
import '../../css/p/p2yqjtb5v.css';
import '../../css/e/eqj3blpeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zzjn3zb4d"/><path class="li792gxac"/><path class="p2yqjtb5v"/><path class="eqj3blpeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:factory-emissions-20-bold" /></template>
