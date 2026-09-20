<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn5gmacvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pn5gmacvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:bulb" /></template>
