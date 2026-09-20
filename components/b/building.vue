<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvqep1bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="wvqep1bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:building" /></template>
