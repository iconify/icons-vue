<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqrud2bhn.css';
import '../../css/u/u_h_b-bhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<rect class="wqrud2bhn"/><path class="u_h_b-bhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:facebook" /></template>
