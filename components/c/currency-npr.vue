<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msf46bcth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msf46bcth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:currency-npr" /></template>
