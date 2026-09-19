<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwrkaoe0y.css';
import '../../css/o/oedplzbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwrkaoe0y"/><path class="oedplzbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:collocation" /></template>
