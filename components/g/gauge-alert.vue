<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or9cg0bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or9cg0bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:gauge-alert" /></template>
