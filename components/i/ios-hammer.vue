<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz5lj8u_t.css';
import '../../css/r/rigcembux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pz5lj8u_t"/><path class="rigcembux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-hammer" /></template>
