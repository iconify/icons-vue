<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci15di65n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci15di65n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-award" /></template>
