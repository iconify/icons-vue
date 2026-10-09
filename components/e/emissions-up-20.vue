<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzjn5iovv.css';
import '../../css/m/mignyccut.css';
import '../../css/u/uq81wcb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xzjn5iovv"/><path class="mignyccut"/><path class="uq81wcb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:emissions-up-20" /></template>
