<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx2hbdw_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="fx2hbdw_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:6-square" /></template>
