<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djun2xb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djun2xb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:celsius" /></template>
