<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0qpmvhbh.css';
import '../../css/x/xysj39n-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="s0qpmvhbh"/><path class="xysj39n-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:digitalocean" /></template>
