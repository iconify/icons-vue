<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrvjxe57d.css';
import '../../css/u/uh0ujnbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jrvjxe57d"/><path class="uh0ujnbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-ring-20" /></template>
