<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qofhu851b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qofhu851b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:hospital-alt-1-line" /></template>
