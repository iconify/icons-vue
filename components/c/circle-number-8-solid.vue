<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqasitbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqasitbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-number-8-solid" /></template>
