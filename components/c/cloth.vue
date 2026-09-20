<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osa6iacrl.css';
import '../../css/v/vv3o_rb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="osa6iacrl"/><path class="vv3o_rb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:cloth" /></template>
