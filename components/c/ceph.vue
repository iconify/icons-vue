<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3l3y1bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m3l3y1bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ceph" /></template>
