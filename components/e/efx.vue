<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4g3y663w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w4g3y663w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:efx" /></template>
