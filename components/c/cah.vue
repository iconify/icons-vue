<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu68r3blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iu68r3blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cah" /></template>
