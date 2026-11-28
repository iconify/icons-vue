<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l00os67mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l00os67mc primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-pin-duotone" /></template>
