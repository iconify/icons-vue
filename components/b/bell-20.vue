<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7p6popon.css';
import '../../css/u/uzzfsfvad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r7p6popon"/><path class="uzzfsfvad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-20" /></template>
