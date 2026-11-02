<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn47rw0ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn47rw0ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:card-sim-line" /></template>
