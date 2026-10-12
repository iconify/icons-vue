<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hryueux2x.css';
import '../../css/g/gmupky7wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hryueux2x"/><path class="gmupky7wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cargo-ship-20" /></template>
