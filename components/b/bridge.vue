<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg1xxrm6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mg1xxrm6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bridge" /></template>
