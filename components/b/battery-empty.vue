<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_z2tacpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="j_z2tacpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:battery-empty" /></template>
