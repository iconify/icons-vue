<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb95o6e0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb95o6e0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:computer-desk-01" /></template>
