<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oynp_94rk.css';
import '../../css/s/spuk--beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oynp_94rk"/><path class="spuk--beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-down-left-20-bold" /></template>
