<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffd1q6b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ffd1q6b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:ethereum-circle-solid" /></template>
