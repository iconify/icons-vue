<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2om87bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d2om87bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:grocery" /></template>
