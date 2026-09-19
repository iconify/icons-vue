<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk0ow5b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk0ow5b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-caret-left-circle" /></template>
