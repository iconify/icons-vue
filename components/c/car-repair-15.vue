<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-7so2bbd.css';
import '../../css/n/nna3xilgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m-7so2bbd"/><path class="nna3xilgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:car-repair-15" /></template>
