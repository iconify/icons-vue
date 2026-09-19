<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjqg-lw3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjqg-lw3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bell" /></template>
