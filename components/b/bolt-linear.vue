<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd1l1p81t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd1l1p81t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bolt-linear" /></template>
