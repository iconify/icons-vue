<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jip_kv-6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="jip_kv-6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:abacus" /></template>
