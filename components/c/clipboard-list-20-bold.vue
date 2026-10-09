<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0ne4_zha.css';
import '../../css/v/vltx34bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k0ne4_zha"/><path class="vltx34bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clipboard-list-20-bold" /></template>
