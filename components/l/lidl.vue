<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzn1nb-_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzn1nb-_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lidl" /></template>
