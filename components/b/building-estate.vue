<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws56w0zmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws56w0zmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-estate" /></template>
