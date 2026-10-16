<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soauwjbuz.css';
import '../../css/x/xqe1shbes.css';
import '../../css/w/wp_1hutrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="soauwjbuz"/><path class="xqe1shbes"/><path class="wp_1hutrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-holder-20-bold" /></template>
