<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzd27gicd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="kzd27gicd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:eatin" /></template>
