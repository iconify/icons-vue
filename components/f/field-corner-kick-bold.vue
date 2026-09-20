<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl91_bbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jl91_bbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:field-corner-kick-bold" /></template>
