<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_dc_jjcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c_dc_jjcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fogo" /></template>
