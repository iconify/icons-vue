<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmc87mbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmc87mbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:flag-solid" /></template>
