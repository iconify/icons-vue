<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhgdjcclt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhgdjcclt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cafe" /></template>
